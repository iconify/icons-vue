<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbqh0mb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbqh0mb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:page-setting-solid" /></template>
