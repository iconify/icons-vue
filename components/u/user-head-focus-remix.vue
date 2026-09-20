<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4kwoob5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4kwoob5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-head-focus-remix" /></template>
