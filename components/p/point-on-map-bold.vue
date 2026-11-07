<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydzcg6vpe.css';
import '../../css/m/m20a56bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydzcg6vpe"/><path clip-rule="evenodd" class="m20a56bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-bold" /></template>
