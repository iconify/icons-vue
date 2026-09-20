<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqttwzbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mqttwzbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-minus2" /></template>
