<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mal05lbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mal05lbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-backward-thin" /></template>
