<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgsozi8rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2208,"height":1440};
const content = `<path class="rgsozi8rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:yahoo-japan" /></template>
