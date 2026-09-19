<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6bthe32v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="j6bthe32v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:masks-theater" /></template>
