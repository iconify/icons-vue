<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z44o-kmxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z44o-kmxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-closed-variant" /></template>
