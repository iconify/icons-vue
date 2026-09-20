<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_svr_bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x_svr_bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-in-love-solid" /></template>
