<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs0i7_h4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs0i7_h4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape-polygon-add" /></template>
