<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc7ct3nlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hc7ct3nlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mango" /></template>
