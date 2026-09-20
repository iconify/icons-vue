<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za4hbfb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za4hbfb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swap-horizontal-circle" /></template>
