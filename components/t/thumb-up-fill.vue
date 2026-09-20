<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ver42fbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ver42fbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:thumb-up-fill" /></template>
