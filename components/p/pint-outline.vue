<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_7-lqjyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_7-lqjyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pint-outline" /></template>
