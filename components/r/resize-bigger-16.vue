<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj2ftacnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jj2ftacnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:resize-bigger-16" /></template>
