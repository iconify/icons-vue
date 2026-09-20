<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzx0rv3rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzx0rv3rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mobile-me-logo-block" /></template>
