<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whl_gzbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whl_gzbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spinrilla-logo-block" /></template>
