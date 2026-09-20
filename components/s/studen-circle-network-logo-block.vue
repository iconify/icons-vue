<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axzo35bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axzo35bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:studen-circle-network-logo-block" /></template>
