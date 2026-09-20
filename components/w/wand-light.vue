<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq1pttxqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq1pttxqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:wand-light" /></template>
