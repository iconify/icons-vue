<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlqp-6bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlqp-6bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:visible" /></template>
