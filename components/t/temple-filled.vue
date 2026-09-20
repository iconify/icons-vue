<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fujky4qvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fujky4qvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:temple-filled" /></template>
