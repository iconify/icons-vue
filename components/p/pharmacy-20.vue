<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfxffib8l.css';
import '../../css/w/we7578b5j.css';
import '../../css/q/qpludsmxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kfxffib8l"/><path class="we7578b5j"/><path class="qpludsmxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pharmacy-20" /></template>
