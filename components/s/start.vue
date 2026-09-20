<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-em6zb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-em6zb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:start" /></template>
