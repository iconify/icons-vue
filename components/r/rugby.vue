<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6eznkbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6eznkbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rugby" /></template>
