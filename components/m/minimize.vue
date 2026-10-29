<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyj-7ezxh.css';
import '../../css/q/q1n0ufkxq.css';
import '../../css/n/nofshwblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj-7ezxh wm-shadow"/><path class="q1n0ufkxq wm-k"/><path class="nofshwblh wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:minimize" /></template>
