<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m99dslsql.css';
import '../../css/x/xmhlqvb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m99dslsql"/><path class="xmhlqvb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pi-48" /></template>
