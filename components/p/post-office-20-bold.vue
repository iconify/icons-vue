<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krbuex_sg.css';
import '../../css/p/pv8po1b5r.css';
import '../../css/f/fvs6qwbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="krbuex_sg"/><path class="pv8po1b5r"/><path class="fvs6qwbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:post-office-20-bold" /></template>
