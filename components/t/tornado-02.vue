<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kj4tflr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kj4tflr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tornado-02" /></template>
