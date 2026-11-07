<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_o_lwkuc.css';
import '../../css/x/xjaw9ykwq.css';
import '../../css/x/xri1c9bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_o_lwkuc"/><path class="xjaw9ykwq"/><path clip-rule="evenodd" class="xri1c9bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-circle-bold" /></template>
