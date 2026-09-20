<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msu-j-bsq.css';
import '../../css/j/j4ehiv-dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="msu-j-bsq"/><path class="j4ehiv-dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pen-to-square" /></template>
