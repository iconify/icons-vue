<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8vetgc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8vetgc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:registered-trademark" /></template>
