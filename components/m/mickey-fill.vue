<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfy1igbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfy1igbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mickey-fill" /></template>
