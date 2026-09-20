<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqor_-z0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqor_-z0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rss-symbol-remix" /></template>
