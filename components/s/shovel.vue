<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhi3h8bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="fhi3h8bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shovel" /></template>
