<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihpmtnj8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihpmtnj8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-8" /></template>
