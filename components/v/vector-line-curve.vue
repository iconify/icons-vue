<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dytkoubrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dytkoubrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:vector-line-curve" /></template>
