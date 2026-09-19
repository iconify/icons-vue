<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqq-_hb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="hqq-_hb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mediarepeat" /></template>
