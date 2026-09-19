<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqacljb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqacljb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-dots" /></template>
