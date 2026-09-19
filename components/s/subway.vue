<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvj_c3ucr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="vvj_c3ucr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:subway" /></template>
