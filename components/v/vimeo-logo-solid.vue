<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs3tun8sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3tun8sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vimeo-logo-solid" /></template>
