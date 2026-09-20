<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8toyb40z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8toyb40z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-2-line" /></template>
