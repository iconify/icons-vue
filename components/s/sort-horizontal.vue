<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6pz_sbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6pz_sbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sort-horizontal" /></template>
