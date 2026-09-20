<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr_wgacjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr_wgacjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:spotify-logo-block" /></template>
