<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqd7-fwmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lqd7-fwmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sleep-remix" /></template>
