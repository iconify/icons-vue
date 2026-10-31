<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtrmvko-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtrmvko-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-incoming-fill-round" /></template>
