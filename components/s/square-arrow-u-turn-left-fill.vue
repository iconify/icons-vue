<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgcrxl56t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lgcrxl56t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-u-turn-left-fill" /></template>
