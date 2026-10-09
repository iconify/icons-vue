<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nehc85b4d.css';
import '../../css/g/gjporh8py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nehc85b4d"/><path class="gjporh8py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-search-20-bold" /></template>
