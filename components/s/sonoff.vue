<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-vpgbc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-vpgbc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonoff" /></template>
