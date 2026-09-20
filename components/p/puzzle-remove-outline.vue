<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpzq2jbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpzq2jbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-remove-outline" /></template>
