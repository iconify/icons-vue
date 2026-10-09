<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3kg39hqy.css';
import '../../css/e/exsoqbbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w3kg39hqy"/><path class="exsoqbbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelchair-20-bold" /></template>
