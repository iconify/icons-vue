<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa3s2nbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa3s2nbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:streamplay-logo-block" /></template>
