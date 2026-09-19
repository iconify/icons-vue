<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unwlo-bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unwlo-bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:open-outline" /></template>
