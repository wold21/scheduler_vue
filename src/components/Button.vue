<template>
    <button v-on:click="onClick()" :style="{background : color}" class="btn">{{text}}</button>
</template>

<script>
export default {
    name : 'Button',
    props : {
        text : String,
        color : String,
    },
    methods : {
        onClick() {
<<<<<<< HEAD
            this.$emit('btn-click')
=======
             this.$emit('btn-click')
>>>>>>> 37e3929aec2cdb1b121746b6b09575c58eec9643
        }
    }

}
</script>