<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9w1vgtit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9w1vgtit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:undo" /></template>
