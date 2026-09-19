<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqsscmszj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqsscmszj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:train-filled" /></template>
