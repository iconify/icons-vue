<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkr0jbczq.css';
import '../../css/e/e66ctgbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkr0jbczq secondary"/><path class="e66ctgbgu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:union-duo" /></template>
