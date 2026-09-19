<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohhcwambf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="ohhcwambf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:map-marker" /></template>
