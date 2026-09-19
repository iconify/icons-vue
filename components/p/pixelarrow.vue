<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_o02bbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l_o02bbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelarrow" /></template>
