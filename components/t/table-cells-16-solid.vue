<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5b5kzb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5b5kzb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:table-cells-16-solid" /></template>
