<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/temu-lr3v.css';
import '../../css/n/nbj6_5v5v.css';
import '../../css/t/t6587jiay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="temu-lr3v"/><path class="nbj6_5v5v"/><path class="t6587jiay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ship-20-bold" /></template>
