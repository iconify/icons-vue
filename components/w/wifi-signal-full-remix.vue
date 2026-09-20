<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emqywvbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="emqywvbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-signal-full-remix" /></template>
