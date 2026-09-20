<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x84wkm2wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x84wkm2wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker-circle" /></template>
