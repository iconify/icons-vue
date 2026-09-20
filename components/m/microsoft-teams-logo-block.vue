<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlg_8-b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlg_8-b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-teams-logo-block" /></template>
