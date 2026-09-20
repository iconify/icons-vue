<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue9ks4bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9ks4bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:take-two-interactive-software" /></template>
