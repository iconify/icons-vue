<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1g56ob0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1g56ob0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-off" /></template>
