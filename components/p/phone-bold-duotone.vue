<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnl-77aoj.css';
import '../../css/w/wsnzclbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnl-77aoj"/><path class="wsnzclbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-bold-duotone" /></template>
