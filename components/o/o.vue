<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi70slb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qi70slb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:o" /></template>
