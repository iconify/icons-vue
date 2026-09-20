<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rct38-bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rct38-bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-left-outline" /></template>
