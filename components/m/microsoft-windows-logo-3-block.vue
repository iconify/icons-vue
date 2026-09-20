<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6ogpabaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6ogpabaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-3-block" /></template>
