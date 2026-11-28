<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lff_3fe-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lff_3fe-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pentagon" /></template>
