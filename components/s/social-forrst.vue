<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnqtz66sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hnqtz66sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-forrst" /></template>
