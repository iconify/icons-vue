<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr6xyx3_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gr6xyx3_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:unity" /></template>
