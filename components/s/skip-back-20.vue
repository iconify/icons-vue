<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acf1ytbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="acf1ytbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skip-back-20" /></template>
