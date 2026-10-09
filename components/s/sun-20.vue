<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poz0mu_8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="poz0mu_8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-20" /></template>
