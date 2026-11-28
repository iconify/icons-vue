<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02ri5zjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n02ri5zjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pin-heart" /></template>
