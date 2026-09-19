<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9uz-ybvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r9uz-ybvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:selector" /></template>
