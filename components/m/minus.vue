<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg3y-cbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rg3y-cbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:minus" /></template>
