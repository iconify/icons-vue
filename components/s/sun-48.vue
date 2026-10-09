<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg054wh3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg054wh3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-48" /></template>
