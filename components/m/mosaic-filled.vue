<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-52n4_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-52n4_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:mosaic-filled" /></template>
