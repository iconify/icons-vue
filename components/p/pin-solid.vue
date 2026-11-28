<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifjxbgbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifjxbgbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pin-solid" /></template>
