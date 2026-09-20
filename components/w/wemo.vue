<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrb495m5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrb495m5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wemo" /></template>
