<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1p0lil_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1p0lil_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-low-01" /></template>
