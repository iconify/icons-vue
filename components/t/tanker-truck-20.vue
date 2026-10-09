<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhwezzbsp.css';
import '../../css/b/b_21f101v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bhwezzbsp"/><path class="b_21f101v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tanker-truck-20" /></template>
