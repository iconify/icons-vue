<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr0lxkb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xr0lxkb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-fill" /></template>
