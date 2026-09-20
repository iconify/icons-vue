<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w991bab4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w991bab4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:users-cog-solid" /></template>
