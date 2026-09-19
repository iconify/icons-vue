<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytkv-bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1179,"height":1000};
const content = `<path class="fytkv-bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:ok" /></template>
