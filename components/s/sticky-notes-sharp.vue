<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrw_no2ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrw_no2ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-notes-sharp" /></template>
