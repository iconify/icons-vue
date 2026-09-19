<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh5uf0c8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nh5uf0c8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:safety-cone" /></template>
