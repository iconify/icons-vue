<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii8jenblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ii8jenblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:scroll-torah" /></template>
