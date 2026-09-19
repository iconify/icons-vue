<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i65jsuv-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i65jsuv-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sticky-note" /></template>
