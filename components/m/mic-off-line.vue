<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr3l9zb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr3l9zb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-off-line" /></template>
