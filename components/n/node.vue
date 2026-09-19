<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn-c7l4th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="sn-c7l4th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:node" /></template>
