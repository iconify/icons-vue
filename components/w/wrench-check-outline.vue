<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrw03cjgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrw03cjgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrench-check-outline" /></template>
