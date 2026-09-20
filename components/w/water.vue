<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udb7-vw_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udb7-vw_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:water" /></template>
