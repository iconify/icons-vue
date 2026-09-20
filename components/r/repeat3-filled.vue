<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_c7-bc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_c7-bc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:repeat3-filled" /></template>
