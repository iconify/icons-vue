<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq9kh0lwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq9kh0lwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:snooze-remix" /></template>
