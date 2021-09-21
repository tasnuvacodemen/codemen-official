<template>
    <button type="button" data-id="" class="is-rows-el quick-btn text-blue-900 text-sm font-bold"  @click="update">Update</button>
</template>
<script>
export default {
    name:"UpdateButton",
    props:{
        memberId:String,
    },
    methods:{
        update(){
            console.log('I am updated')
        },
    },
}
</script>