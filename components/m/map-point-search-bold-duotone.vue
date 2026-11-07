<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev04l0b7x.css';
import '../../css/w/wr4eu4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev04l0b7x"/><path clip-rule="evenodd" class="wr4eu4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-search-bold-duotone" /></template>
