<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_jl0xt4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_jl0xt4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:target-dollar-solid" /></template>
