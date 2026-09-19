<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-v_5bcnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="c-v_5bcnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-duo" /></template>
