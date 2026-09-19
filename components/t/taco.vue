<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8xmsiqrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p8xmsiqrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:taco" /></template>
