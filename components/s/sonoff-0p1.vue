<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re2q06o0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re2q06o0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonoff-0p1" /></template>
