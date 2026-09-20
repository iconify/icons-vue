<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkz44uchn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkz44uchn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:safari" /></template>
