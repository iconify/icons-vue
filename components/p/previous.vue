<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh62sw2tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh62sw2tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:previous" /></template>
