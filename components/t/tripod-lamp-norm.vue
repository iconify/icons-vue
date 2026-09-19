<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8in9rrwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8in9rrwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tripod-lamp-norm" /></template>
