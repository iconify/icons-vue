<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj292lbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zj292lbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:wpr" /></template>
