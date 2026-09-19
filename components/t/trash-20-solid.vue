<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6oi_ibfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p6oi_ibfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trash-20-solid" /></template>
