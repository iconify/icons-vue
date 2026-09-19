<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8pdp68ro.css';
import '../../css/s/swz9s6b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w8pdp68ro"/><path class="swz9s6b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scalpel-cursor" /></template>
