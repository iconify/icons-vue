<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u12ihswbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u12ihswbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volcano" /></template>
