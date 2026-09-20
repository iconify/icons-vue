<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8d7f8bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8d7f8bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-vertical-sharp" /></template>
