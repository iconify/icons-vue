<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugquq8b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ugquq8b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plug-with-bolt" /></template>
