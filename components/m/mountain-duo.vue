<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn2ejlbtm.css';
import '../../css/e/eu7gmyhby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2ejlbtm secondary"/><path class="eu7gmyhby primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mountain-duo" /></template>
