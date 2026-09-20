<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w48m7-bwv.css';
import '../../css/r/r4-mswj9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w48m7-bwv"/><path class="r4-mswj9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mod" /></template>
