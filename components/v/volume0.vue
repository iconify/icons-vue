<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj90b9bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wj90b9bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:volume0" /></template>
