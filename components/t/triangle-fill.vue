<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi8nnxn0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi8nnxn0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:triangle-fill" /></template>
