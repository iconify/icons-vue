<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmdrs99jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmdrs99jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-square-filled" /></template>
