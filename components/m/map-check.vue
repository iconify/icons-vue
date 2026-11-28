<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypva6o2qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypva6o2qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-check" /></template>
