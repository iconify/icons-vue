<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrfx1wbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nrfx1wbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rug" /></template>
