<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo-lb0b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="qo-lb0b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:thumb-up" /></template>
