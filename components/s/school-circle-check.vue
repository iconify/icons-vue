<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we3tkpbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="we3tkpbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:school-circle-check" /></template>
