<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu9xycigl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qu9xycigl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shovel-rake-solid" /></template>
