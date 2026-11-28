<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt9cu234p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9cu234p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:panel-bottom" /></template>
