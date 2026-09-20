<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu5wtw1zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu5wtw1zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:plurk-logo-2-solid" /></template>
