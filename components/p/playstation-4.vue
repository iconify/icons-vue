<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx2nqib3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx2nqib3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:playstation-4" /></template>
