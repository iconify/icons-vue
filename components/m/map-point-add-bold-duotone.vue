<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev04l0b7x.css';
import '../../css/y/yp-6u2b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev04l0b7x"/><path class="yp-6u2b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-add-bold-duotone" /></template>
