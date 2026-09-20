<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2p9unbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i2p9unbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:repeat-single-solid" /></template>
