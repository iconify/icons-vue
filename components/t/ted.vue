<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igt75mb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igt75mb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ted" /></template>
