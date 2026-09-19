<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd064tiam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="kd064tiam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pen" /></template>
