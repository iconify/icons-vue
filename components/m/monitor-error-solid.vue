<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mizzllh0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mizzllh0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:monitor-error-solid" /></template>
