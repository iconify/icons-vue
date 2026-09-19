<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-ms6bclb.css';
import '../../css/h/hx5u2eb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x-ms6bclb"/><path class="hx5u2eb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:smoking" /></template>
