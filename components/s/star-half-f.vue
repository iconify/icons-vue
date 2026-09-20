<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf6wqpb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":19};
const content = `<path class="rf6wqpb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:star-half-f" /></template>
