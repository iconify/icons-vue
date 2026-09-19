<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ta79bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ta79bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:network" /></template>
