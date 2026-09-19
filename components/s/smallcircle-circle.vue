<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ils92p-0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ils92p-0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:smallcircle-circle" /></template>
