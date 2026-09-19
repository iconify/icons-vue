<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4sq3bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4sq3bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-firstline-right" /></template>
