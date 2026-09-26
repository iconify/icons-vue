<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo708vpsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo708vpsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-horizontal-linear" /></template>
