<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q548c2bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q548c2bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rectangle-vertical-fill" /></template>
