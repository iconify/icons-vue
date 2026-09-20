<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgnvl2rtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnvl2rtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tags" /></template>
