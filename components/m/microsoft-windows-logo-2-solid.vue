<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx9icybce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx9icybce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-2-solid" /></template>
