<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihk9poypq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihk9poypq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paperclip-duotone-round" /></template>
