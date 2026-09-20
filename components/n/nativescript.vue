<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap71sztlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap71sztlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nativescript" /></template>
