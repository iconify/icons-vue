<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiug0vbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hiug0vbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:shot" /></template>
