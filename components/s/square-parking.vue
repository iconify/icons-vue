<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ualvnw05g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ualvnw05g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-parking" /></template>
