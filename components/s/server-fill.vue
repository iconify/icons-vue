<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_bbk3_og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_bbk3_og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:server-fill" /></template>
