<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxcyr-bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oxcyr-bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-steam" /></template>
