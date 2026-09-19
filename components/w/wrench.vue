<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxqpybcxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gxqpybcxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:wrench" /></template>
