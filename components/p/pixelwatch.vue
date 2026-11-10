<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uepjdpbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uepjdpbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pixelwatch" /></template>
