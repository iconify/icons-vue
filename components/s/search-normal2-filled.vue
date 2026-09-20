<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0tre7b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0tre7b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-normal2-filled" /></template>
