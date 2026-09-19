<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9yt772bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t9yt772bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-low" /></template>
