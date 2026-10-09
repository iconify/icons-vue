<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7aadjbad.css';
import '../../css/l/lthy19bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d7aadjbad"/><path class="lthy19bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paw-20-bold" /></template>
