<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojt__3bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ojt__3bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:turntable" /></template>
