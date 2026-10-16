<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2m6mk_mr.css';
import '../../css/l/ljtf0ybqg.css';
import '../../css/i/ixhsczgzl.css';
import '../../css/s/sxr-mzwmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2m6mk_mr"/><path class="ljtf0ybqg"/><path class="ixhsczgzl"/><path class="sxr-mzwmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-dish-20-bold" /></template>
