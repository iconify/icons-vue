<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t0rrxjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="p2t0rrxjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:object-ungroup" /></template>
