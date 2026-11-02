<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdkmclblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdkmclblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-block-line" /></template>
