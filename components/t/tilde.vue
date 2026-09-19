<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfdw9zbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfdw9zbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tilde" /></template>
