<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf7ewo7jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf7ewo7jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star2-filled" /></template>
