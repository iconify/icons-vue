<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_06govns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_06govns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-bad-bold" /></template>
