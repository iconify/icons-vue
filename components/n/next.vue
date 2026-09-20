<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n62a64b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n62a64b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:next" /></template>
