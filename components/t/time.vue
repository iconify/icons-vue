<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grftfubpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grftfubpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:time" /></template>
