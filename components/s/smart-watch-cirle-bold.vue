<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_w3injsq.css';
import '../../css/r/rwg8vfj3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_w3injsq"/><path class="rwg8vfj3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smart-watch-cirle-bold" /></template>
