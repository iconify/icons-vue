<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arvckpbkx.css';
import '../../css/j/jlgpfub1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arvckpbkx"/><path class="jlgpfub1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:umbrella-48-bold" /></template>
