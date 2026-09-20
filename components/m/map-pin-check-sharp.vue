<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnf8mabbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnf8mabbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-check-sharp" /></template>
