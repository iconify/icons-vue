<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/str6i-nan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="str6i-nan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-3-solid" /></template>
