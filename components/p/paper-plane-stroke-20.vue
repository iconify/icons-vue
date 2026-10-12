<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcerxm02m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kcerxm02m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:paper-plane-stroke-20" /></template>
