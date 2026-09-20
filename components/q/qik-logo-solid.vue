<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rygsn1wuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rygsn1wuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:qik-logo-solid" /></template>
