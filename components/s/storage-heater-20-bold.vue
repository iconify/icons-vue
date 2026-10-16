<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7k-tdrrr.css';
import '../../css/g/g2q5-lbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7k-tdrrr"/><path class="g2q5-lbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storage-heater-20-bold" /></template>
