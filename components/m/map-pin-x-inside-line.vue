<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niczrxotn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niczrxotn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-x-inside-line" /></template>
