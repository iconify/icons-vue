<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu_-_ib9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pu_-_ib9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-check" /></template>
