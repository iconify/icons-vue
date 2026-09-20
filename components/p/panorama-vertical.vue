<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c07jk9b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c07jk9b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama-vertical" /></template>
