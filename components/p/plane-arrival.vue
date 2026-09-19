<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d18g1tbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d18g1tbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:plane-arrival" /></template>
