<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmecbubtg.css';
import '../../css/q/qqeg1x_1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmecbubtg"/><path class="qqeg1x_1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:robot-2-filled" /></template>
