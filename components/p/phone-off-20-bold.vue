<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8o5orx4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d8o5orx4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-off-20-bold" /></template>
