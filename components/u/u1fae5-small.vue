<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ia12bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l9ia12bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1fae5-small" /></template>
