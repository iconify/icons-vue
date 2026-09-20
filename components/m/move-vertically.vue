<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqt54qsrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jqt54qsrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:move-vertically" /></template>
