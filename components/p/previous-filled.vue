<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjo5k1bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo5k1bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:previous-filled" /></template>
