<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyai-pb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1664};
const content = `<path class="zyai-pb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:vine" /></template>
