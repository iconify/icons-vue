<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0v27dbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v0v27dbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:terminal-square-filled" /></template>
