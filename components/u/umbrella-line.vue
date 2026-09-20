<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfo81w0ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfo81w0ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:umbrella-line" /></template>
