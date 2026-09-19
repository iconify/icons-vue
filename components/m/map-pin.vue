<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt9f3ub2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gt9f3ub2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:map-pin" /></template>
