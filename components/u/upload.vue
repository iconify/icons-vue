<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or20avb8e.css';
import '../../css/u/uotgxeb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or20avb8e"/><path class="uotgxeb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:upload" /></template>
