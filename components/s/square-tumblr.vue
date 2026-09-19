<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xov3r3xqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xov3r3xqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-tumblr" /></template>
