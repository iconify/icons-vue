<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvskalk6x.css';
import '../../css/y/ychu0ub8d.css';
import '../../css/j/jy7ylib9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nvskalk6x"/><path class="ychu0ub8d"/><path class="jy7ylib9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rowing-20" /></template>
