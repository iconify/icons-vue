<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2hh6_blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2hh6_blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-off-fill" /></template>
