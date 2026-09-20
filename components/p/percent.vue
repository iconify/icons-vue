<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4k4dsb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4k4dsb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:percent" /></template>
