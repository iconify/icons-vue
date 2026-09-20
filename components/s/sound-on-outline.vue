<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq_e61vnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tq_e61vnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sound-on-outline" /></template>
