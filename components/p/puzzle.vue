<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2-go7evs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":32};
const content = `<path class="m2-go7evs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:puzzle" /></template>
