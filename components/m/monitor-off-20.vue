<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7x5yta8s.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/p/pssx0khhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l7x5yta8s"/><path class="kvl9ucc0s"/><path class="pssx0khhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-off-20" /></template>
