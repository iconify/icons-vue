<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oll7jobqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":464};
const content = `<path class="oll7jobqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:rotate-cw" /></template>
