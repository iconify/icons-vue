<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utr3r6_dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utr3r6_dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:reply-24" /></template>
