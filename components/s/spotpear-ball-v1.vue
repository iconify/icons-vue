<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob56-7b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob56-7b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotpear-ball-v1" /></template>
