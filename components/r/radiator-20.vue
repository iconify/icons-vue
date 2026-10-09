<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq6nfxbav.css';
import '../../css/e/eyqb_0bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kq6nfxbav"/><path class="eyqb_0bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiator-20" /></template>
