<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/a/a2wqv6phc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="a2wqv6phc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:robot-vacuum-20-bold" /></template>
