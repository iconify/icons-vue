<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfvc9yb6v.css';
import '../../css/z/zg5f-yb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qfvc9yb6v"/><path class="zg5f-yb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticker-20" /></template>
