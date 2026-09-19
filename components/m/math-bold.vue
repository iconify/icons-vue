<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_8et7y8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g_8et7y8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:math-bold" /></template>
