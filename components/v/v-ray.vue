<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1bpbxm2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1bpbxm2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:v-ray" /></template>
