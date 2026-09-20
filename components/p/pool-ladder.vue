<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-z1hcbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o-z1hcbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pool-ladder" /></template>
