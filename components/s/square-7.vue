<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsf8_ubdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsf8_ubdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-7" /></template>
