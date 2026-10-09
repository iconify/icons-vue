<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc9t8fp5n.css';
import '../../css/n/nl5mucbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hc9t8fp5n"/><path class="nl5mucbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-light-48" /></template>
