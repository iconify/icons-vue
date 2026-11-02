<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt8t0bbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt8t0bbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-3-line" /></template>
