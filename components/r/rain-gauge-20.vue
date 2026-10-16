<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihcg3e6qc.css';
import '../../css/n/nnq4tpzbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ihcg3e6qc"/><path class="nnq4tpzbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rain-gauge-20" /></template>
