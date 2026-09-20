<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxs0vnbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxs0vnbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:telos" /></template>
