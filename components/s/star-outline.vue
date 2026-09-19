<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_qy5_tac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="b_qy5_tac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-outline" /></template>
