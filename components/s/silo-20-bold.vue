<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljgv6abmg.css';
import '../../css/x/xhptmubfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljgv6abmg"/><path class="xhptmubfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silo-20-bold" /></template>
