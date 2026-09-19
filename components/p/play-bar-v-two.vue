<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t67x14b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t67x14b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-v-two" /></template>
