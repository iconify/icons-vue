<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgodc5u1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgodc5u1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-5-box" /></template>
