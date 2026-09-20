<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnm9e3w-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnm9e3w-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-1-block" /></template>
