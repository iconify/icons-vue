<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh02dzb5a.css';
import '../../css/u/ufrf-lbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rh02dzb5a"/><path class="ufrf-lbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-desc-20" /></template>
