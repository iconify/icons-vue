<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy5uidbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iy5uidbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-lockers" /></template>
