<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkis0cc-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkis0cc-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-guest-room" /></template>
