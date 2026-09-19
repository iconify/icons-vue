<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-d7wubaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-d7wubaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:medal-1st-solid" /></template>
