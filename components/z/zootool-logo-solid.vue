<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trm18ccjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trm18ccjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zootool-logo-solid" /></template>
