<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbb5sxb8o.css';
import '../../css/g/g74pk9c5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbb5sxb8o"/><path class="g74pk9c5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microplastics-48-bold" /></template>
