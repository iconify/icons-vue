<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw1fx7b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw1fx7b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scilab" /></template>
