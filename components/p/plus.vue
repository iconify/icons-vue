<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt_5ujbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wt_5ujbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:plus" /></template>
