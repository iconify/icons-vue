<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2lc4yp1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2lc4yp1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:meta-cafe-logo-block" /></template>
