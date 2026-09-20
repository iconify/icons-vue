<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx0gpq2uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qx0gpq2uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-dynamics-logo-block" /></template>
