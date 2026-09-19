<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqfvm8biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jqfvm8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-group" /></template>
