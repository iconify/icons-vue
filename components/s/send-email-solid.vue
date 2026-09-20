<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdoj7busb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kdoj7busb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:send-email-solid" /></template>
