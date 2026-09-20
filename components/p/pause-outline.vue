<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlfh2fb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dlfh2fb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:pause-outline" /></template>
