<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9nycrbpr.css';
import '../../css/e/e0maw8b-r.css';
import '../../css/h/hjnsd4bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9nycrbpr"/><path class="e0maw8b-r"/><path class="hjnsd4bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rvst" /></template>
