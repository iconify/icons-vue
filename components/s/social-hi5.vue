<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1o-cjme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cu1o-cjme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-hi5" /></template>
