<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0cbf1blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0cbf1blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yoast" /></template>
