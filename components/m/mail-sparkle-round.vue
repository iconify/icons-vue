<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phnq44bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phnq44bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-sparkle-round" /></template>
