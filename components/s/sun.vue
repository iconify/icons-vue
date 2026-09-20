<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h69r-hbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h69r-hbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sun" /></template>
