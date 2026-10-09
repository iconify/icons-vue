<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kavo--bbr.css';
import '../../css/l/ll5uu22sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kavo--bbr"/><path class="ll5uu22sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-48-bold" /></template>
