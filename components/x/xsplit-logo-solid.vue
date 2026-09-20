<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-67u_bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-67u_bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xsplit-logo-solid" /></template>
