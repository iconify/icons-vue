<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/selaf8bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="selaf8bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tablet-fill" /></template>
