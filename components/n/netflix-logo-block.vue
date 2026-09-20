<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtp73sc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtp73sc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:netflix-logo-block" /></template>
