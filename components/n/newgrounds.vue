<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwp5elblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwp5elblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:newgrounds" /></template>
