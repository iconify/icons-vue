<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0f51ulgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u0f51ulgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-envelope-solid" /></template>
