<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyfh41bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfh41bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-duotone-round" /></template>
