<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0_j2mtzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="q0_j2mtzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:user" /></template>
