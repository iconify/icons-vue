<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_km9mbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_km9mbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:redo-variant" /></template>
