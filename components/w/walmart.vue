<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0m3atbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":532.262,"height":600};
const content = `<path class="k0m3atbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:walmart" /></template>
