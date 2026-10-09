<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q85exbg4c.css';
import '../../css/s/sy0-p47dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q85exbg4c"/><path class="sy0-p47dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screwdriver-20" /></template>
