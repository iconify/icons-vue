<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3k-9dnhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3k-9dnhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-cellular-3" /></template>
