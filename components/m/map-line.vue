<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnpa_2wmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnpa_2wmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-line" /></template>
