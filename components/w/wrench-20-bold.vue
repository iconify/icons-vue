<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlfvtxb2w.css';
import '../../css/l/lylog5b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tlfvtxb2w"/><path class="lylog5b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wrench-20-bold" /></template>
