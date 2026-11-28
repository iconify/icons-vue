<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq0s9vbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq0s9vbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:package-check-solid" /></template>
