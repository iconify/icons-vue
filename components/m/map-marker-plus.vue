<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrnwgv0ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrnwgv0ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-marker-plus" /></template>
