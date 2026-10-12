<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3ht3i_xn.css';
import '../../css/n/n--zs0bqk.css';
import '../../css/v/v5pwrda9h.css';
import '../../css/m/m-9fczbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ht3i_xn"/><path class="n--zs0bqk"/><path class="v5pwrda9h"/><path class="m-9fczbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:town-hall-20-bold" /></template>
