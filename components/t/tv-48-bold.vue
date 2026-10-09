<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw937uq7x.css';
import '../../css/h/h8hd6s8wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw937uq7x"/><path class="h8hd6s8wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tv-48-bold" /></template>
