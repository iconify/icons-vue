<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpg9p2bhv.css';
import '../../css/l/l05mycboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hpg9p2bhv"/><path class="l05mycboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paragraph-20-bold" /></template>
