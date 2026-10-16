<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh3g0ib5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hh3g0ib5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-star-20" /></template>
