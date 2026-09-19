<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-sbngbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v-sbngbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-lab-research-syringe" /></template>
