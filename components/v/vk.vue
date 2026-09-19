<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trs3z3bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="trs3z3bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:vk" /></template>
