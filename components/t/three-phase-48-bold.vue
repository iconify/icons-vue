<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcunuwblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zcunuwblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:three-phase-48-bold" /></template>
