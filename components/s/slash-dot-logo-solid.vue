<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxyvz461p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pxyvz461p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:slash-dot-logo-solid" /></template>
