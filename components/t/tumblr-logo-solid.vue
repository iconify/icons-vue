<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut7h2oafm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut7h2oafm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tumblr-logo-solid" /></template>
