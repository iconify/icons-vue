<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6w9hdc9o.css';
import '../../css/p/pi1hrbbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p6w9hdc9o"/><path class="pi1hrbbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pizza-slice-20-bold" /></template>
