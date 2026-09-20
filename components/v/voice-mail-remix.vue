<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh9114-ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh9114-ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-mail-remix" /></template>
