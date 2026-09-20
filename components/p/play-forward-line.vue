<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-x2zkbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-x2zkbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-forward-line" /></template>
