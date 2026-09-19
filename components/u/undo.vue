<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0nmo15_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0nmo15_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:undo" /></template>
