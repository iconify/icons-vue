<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo5-_oboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qo5-_oboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:maple-leaf-bold" /></template>
