<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry4ptt9wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ry4ptt9wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scale-20-solid" /></template>
