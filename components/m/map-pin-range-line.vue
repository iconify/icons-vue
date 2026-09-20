<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jybtk96am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jybtk96am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-range-line" /></template>
