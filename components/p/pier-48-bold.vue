<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdclrrbld.css';
import '../../css/z/zu1wjac1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdclrrbld"/><path class="zu1wjac1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pier-48-bold" /></template>
