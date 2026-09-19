<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tosodm3wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tosodm3wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:x-circle-20-solid" /></template>
