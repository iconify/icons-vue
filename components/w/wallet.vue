<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5t6vubnr.css';
import '../../css/o/ow_l13b0g.css';
import '../../css/a/ambai7ovl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z5t6vubnr"/><path class="ow_l13b0g"/><path class="ambai7ovl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:wallet" /></template>
