<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lob17sbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lob17sbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:plurk-logo-3-block" /></template>
