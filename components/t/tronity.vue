<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucjl0me4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucjl0me4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tronity" /></template>
