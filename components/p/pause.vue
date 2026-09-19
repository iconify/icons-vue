<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty0_57byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ty0_57byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:pause" /></template>
