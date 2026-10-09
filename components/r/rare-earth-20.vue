<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aooe7jbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aooe7jbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rare-earth-20" /></template>
