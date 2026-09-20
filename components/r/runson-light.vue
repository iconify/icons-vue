<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsz5w_b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zsz5w_b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:runson-light" /></template>
