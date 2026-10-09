<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de63-bcoq.css';
import '../../css/g/gmk8tebem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="de63-bcoq"/><path class="gmk8tebem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noise-reduction-48-bold" /></template>
