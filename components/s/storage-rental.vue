<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_c3n_rwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k_c3n_rwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:storage-rental" /></template>
