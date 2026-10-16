<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/t/tyrfmtb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="tyrfmtb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-charger-20-bold" /></template>
