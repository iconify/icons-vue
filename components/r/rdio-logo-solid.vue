<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swa6fxbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swa6fxbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:rdio-logo-solid" /></template>
