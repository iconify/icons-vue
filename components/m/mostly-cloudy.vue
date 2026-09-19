<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p82xsdujf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p82xsdujf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:mostly-cloudy" /></template>
