<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdpw95c_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdpw95c_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-alert-fill" /></template>
