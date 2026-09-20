<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l61g_dw_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l61g_dw_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shoe-2-fill" /></template>
