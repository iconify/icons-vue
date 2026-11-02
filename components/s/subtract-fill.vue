<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxhwlyq0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxhwlyq0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtract-fill" /></template>
