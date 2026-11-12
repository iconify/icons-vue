<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni_g83x2x.css';
import '../../css/a/a4a1azmng.css';
import '../../css/g/g11ghhn1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni_g83x2x"/><path class="a4a1azmng"/><path class="g11ghhn1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redis-dark" /></template>
