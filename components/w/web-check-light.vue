<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh5eilbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kh5eilbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:web-check-light" /></template>
