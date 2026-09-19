<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy7tywbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy7tywbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twitch" /></template>
