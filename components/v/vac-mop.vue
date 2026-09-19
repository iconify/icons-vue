<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8attu2qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8attu2qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vac-mop" /></template>
