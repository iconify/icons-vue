<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itv2ip3np.css';
import '../../css/w/wio05-bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itv2ip3np"/><path clip-rule="evenodd" class="wio05-bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-stars-line" /></template>
