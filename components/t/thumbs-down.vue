<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7imp4bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7imp4bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:thumbs-down" /></template>
