<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urg8vg02i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="urg8vg02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:twitter-logo" /></template>
