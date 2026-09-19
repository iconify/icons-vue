<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7fq4xbnr.css';
import '../../css/w/wg5_tobjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7fq4xbnr"/><path class="wg5_tobjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:passport-1" /></template>
