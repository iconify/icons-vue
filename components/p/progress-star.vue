<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6l7oo_-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6l7oo_-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:progress-star" /></template>
