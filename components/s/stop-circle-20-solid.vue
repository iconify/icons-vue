<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm1-l0cmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jm1-l0cmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:stop-circle-20-solid" /></template>
