<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3t5tecsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="p3t5tecsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:no-dogs" /></template>
