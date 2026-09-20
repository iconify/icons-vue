<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsse2tbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsse2tbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shrink-vertical" /></template>
