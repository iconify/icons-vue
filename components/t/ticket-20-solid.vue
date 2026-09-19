<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfij42n3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rfij42n3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ticket-20-solid" /></template>
