<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9wovjvct.css';
import '../../css/s/sx3zuyn8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b9wovjvct"/><path class="sx3zuyn8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-bank-20-bold" /></template>
