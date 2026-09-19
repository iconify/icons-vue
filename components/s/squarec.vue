<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_lklgblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="e_lklgblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarec" /></template>
