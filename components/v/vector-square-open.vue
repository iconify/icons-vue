<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zax7p-bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zax7p-bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-square-open" /></template>
