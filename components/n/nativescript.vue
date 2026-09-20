<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im3f2_frr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im3f2_frr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nativescript" /></template>
