<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvmu1sb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wvmu1sb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:marker" /></template>
