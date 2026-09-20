<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3ztu-p5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3ztu-p5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-1-solid" /></template>
