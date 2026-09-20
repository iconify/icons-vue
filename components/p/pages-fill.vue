<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy_osdbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_osdbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pages-fill" /></template>
