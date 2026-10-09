<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4d9q7zmc.css';
import '../../css/z/zto9ilb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4d9q7zmc"/><path class="zto9ilb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-20" /></template>
