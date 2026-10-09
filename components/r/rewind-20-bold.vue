<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q06plnibn.css';
import '../../css/b/bb-6nmboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q06plnibn"/><path class="bb-6nmboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rewind-20-bold" /></template>
