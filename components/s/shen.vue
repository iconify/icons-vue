<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9lipul9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9lipul9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:shen" /></template>
