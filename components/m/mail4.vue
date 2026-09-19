<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x99r71mke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x99r71mke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mail4" /></template>
