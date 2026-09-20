<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5jv108xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j5jv108xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trend-sideways-circle" /></template>
