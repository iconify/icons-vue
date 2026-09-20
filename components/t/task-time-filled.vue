<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_hxwwbci.css';
import '../../css/m/m4fm11vel.css';
import '../../css/e/ezy_p22ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="m4fm11vel"/><path class="ezy_p22ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-time-filled" /></template>
