<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofts-6g4o.css';
import '../../css/c/cqvp3bvcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="cqvp3bvcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-20" /></template>
