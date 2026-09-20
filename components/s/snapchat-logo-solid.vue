<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-omnkb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-omnkb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:snapchat-logo-solid" /></template>
