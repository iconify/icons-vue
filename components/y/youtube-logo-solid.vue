<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkw-3rbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkw-3rbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-logo-solid" /></template>
