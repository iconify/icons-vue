<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjg8qor2a.css';
import '../../css/k/kyzz2cc9p.css';
import '../../css/l/l9lokr6ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xjg8qor2a"/><path class="kyzz2cc9p"/><path class="l9lokr6ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-wrench-48-bold" /></template>
