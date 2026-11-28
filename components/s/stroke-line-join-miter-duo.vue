<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je1_p6b6p.css';
import '../../css/i/irsgehcir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je1_p6b6p secondary"/><path class="irsgehcir primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-miter-duo" /></template>
