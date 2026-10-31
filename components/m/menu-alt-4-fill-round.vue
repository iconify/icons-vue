<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuz-0actz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuz-0actz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-4-fill-round" /></template>
