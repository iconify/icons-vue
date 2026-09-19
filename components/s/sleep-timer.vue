<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whkglzwwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whkglzwwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sleep-timer" /></template>
