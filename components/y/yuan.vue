<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsj9wgbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lsj9wgbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:yuan" /></template>
