<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oex3cvbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oex3cvbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:optimize" /></template>
