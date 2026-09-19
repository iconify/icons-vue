<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kueda4bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kueda4bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:volume-plus" /></template>
