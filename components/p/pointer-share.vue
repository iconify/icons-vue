<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/map0j7bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="map0j7bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-share" /></template>
