<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s97pvnh2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s97pvnh2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:send-plane-line" /></template>
