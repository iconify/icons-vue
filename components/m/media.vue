<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onfg9s0lo.css';
import '../../css/l/l1tk6nbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onfg9s0lo"/><path class="l1tk6nbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:media" /></template>
