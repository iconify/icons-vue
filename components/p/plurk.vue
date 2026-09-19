<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd_9zebhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pd_9zebhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:plurk" /></template>
