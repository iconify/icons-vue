<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xixbvxbcd.css';
import '../../css/s/sboz3ieoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xixbvxbcd"/><path class="sboz3ieoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sd-card-download-bold" /></template>
