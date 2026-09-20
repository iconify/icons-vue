<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvi_e_b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvi_e_b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smart-card-off-outline" /></template>
