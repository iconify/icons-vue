<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baag32u7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="baag32u7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-2-duo" /></template>
