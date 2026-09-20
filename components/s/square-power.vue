<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7mc-_bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7mc-_bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-power" /></template>
