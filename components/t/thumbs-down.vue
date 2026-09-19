<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j79x-vugx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j79x-vugx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:thumbs-down" /></template>
