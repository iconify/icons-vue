<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e81vzdjdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e81vzdjdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:winr" /></template>
