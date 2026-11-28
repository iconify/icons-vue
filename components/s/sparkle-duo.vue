<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt9w2ci5j.css';
import '../../css/r/ryi59f59s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt9w2ci5j secondary"/><path class="primary ryi59f59s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sparkle-duo" /></template>
