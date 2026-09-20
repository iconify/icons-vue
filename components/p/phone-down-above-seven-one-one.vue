<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkbqpoy8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kkbqpoy8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-seven-one-one" /></template>
