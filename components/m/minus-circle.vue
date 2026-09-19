<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxan9g_6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="qxan9g_6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:minus-circle" /></template>
