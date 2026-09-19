<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m46mg6mre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="m46mg6mre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:viadeo" /></template>
