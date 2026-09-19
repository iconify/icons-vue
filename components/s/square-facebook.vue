<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baw6f0ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="baw6f0ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-facebook" /></template>
