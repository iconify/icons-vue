<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb2e_5bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pb2e_5bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-alpha-up" /></template>
