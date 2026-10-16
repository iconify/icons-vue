<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr-sxkt2n.css';
import '../../css/p/poccklbbx.css';
import '../../css/h/hhujsxb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gr-sxkt2n"/><path class="poccklbbx"/><path class="hhujsxb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-wrench-20-bold" /></template>
