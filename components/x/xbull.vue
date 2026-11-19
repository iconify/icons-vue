<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m15x6e6na.css';
import '../../css/k/knxlbdceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m15x6e6na"/><path class="knxlbdceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xbull" /></template>
