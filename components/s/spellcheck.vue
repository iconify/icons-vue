<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcwgvlb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="kcwgvlb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spellcheck" /></template>
