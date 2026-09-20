<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq-m8lbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wq-m8lbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:safari" /></template>
