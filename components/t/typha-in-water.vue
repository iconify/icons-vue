<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to5r_0bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="to5r_0bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:typha-in-water" /></template>
