<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es5jyjbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="es5jyjbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xing-logo-block" /></template>
