<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtcnayb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vtcnayb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:takeaway-box" /></template>
