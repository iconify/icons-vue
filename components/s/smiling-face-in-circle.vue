<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx7y6ebae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qx7y6ebae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smiling-face-in-circle" /></template>
