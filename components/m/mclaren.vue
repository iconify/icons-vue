<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht0_sf_dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht0_sf_dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mclaren" /></template>
