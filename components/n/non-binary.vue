<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slfsep4xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="slfsep4xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:non-binary" /></template>
