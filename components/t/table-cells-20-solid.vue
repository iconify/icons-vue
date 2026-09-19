<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_6z5b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nz_6z5b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:table-cells-20-solid" /></template>
