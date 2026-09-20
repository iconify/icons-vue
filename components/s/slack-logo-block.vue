<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy7d0yvro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy7d0yvro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:slack-logo-block" /></template>
