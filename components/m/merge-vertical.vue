<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qod50dvnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qod50dvnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:merge-vertical" /></template>
