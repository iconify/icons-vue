<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx29l3btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx29l3btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-minus-fill" /></template>
