<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dywh2-b_s.css';
import '../../css/q/qqyc4mb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dywh2-b_s"/><path class="qqyc4mb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopile-20-bold" /></template>
