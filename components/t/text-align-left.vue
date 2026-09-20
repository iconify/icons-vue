<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkapuhbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkapuhbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:text-align-left" /></template>
