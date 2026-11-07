<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoqk-f2dc.css';
import '../../css/i/ixj_x3vjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqk-f2dc"/><path class="ixj_x3vjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-keyhole-bold-duotone" /></template>
