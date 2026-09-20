<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2-cmel8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-cmel8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tidal" /></template>
