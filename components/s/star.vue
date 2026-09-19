<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/praxjquvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="praxjquvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:star" /></template>
