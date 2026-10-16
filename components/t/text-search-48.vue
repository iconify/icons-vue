<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz7crbc0o.css';
import '../../css/l/lp4l0xmec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nz7crbc0o"/><path class="lp4l0xmec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-search-48" /></template>
