<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7m94ibbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7m94ibbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-plus-gloss" /></template>
