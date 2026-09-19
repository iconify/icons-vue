<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr5dqqb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xr5dqqb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-circle-20-solid" /></template>
