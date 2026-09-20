<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o54f7nakg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o54f7nakg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pointer-top" /></template>
