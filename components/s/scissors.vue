<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5w_htbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="j5w_htbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:scissors" /></template>
