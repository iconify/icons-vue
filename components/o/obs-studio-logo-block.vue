<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5s4bo5vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5s4bo5vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:obs-studio-logo-block" /></template>
