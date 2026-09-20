<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrszchuok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrszchuok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:medal-circle" /></template>
