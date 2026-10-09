<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzj6chbuh.css';
import '../../css/r/rjv6740ri.css';
import '../../css/h/h6o3uyb1z.css';
import '../../css/k/kqzeh81us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tzj6chbuh"/><path class="rjv6740ri"/><path class="h6o3uyb1z"/><path class="kqzeh81us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycle-48" /></template>
