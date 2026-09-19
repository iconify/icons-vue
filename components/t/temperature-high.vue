<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe5u3g6sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qe5u3g6sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-high" /></template>
