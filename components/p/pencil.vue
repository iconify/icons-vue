<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-o7sbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yz-o7sbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:pencil" /></template>
