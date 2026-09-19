<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpix1x-gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpix1x-gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:slack-fill" /></template>
