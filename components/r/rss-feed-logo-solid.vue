<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y19neniso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y19neniso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:rss-feed-logo-solid" /></template>
