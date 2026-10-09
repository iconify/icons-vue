<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1wr267gl.css';
import '../../css/z/zq8n3hqfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1wr267gl"/><path class="zq8n3hqfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tent-48-bold" /></template>
