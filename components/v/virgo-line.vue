<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo44_mtta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo44_mtta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:virgo-line" /></template>
