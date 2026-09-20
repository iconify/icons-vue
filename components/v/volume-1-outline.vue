<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmizmbbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rmizmbbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:volume-1-outline" /></template>
