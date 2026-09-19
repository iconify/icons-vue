<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6-ntejpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p6-ntejpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-viadeo" /></template>
