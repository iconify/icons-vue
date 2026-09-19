<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf7vyfbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tf7vyfbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:vest-patches" /></template>
