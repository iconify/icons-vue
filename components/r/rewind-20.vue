<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2dd3q7hq.css';
import '../../css/m/msgtlpbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2dd3q7hq"/><path class="msgtlpbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rewind-20" /></template>
