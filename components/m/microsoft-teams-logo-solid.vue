<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugnveb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gugnveb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-teams-logo-solid" /></template>
