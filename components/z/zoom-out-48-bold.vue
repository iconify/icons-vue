<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-pfn5jar.css';
import '../../css/a/anc-0tb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="anc-0tb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-out-48-bold" /></template>
