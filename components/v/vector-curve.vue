<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvmbfl4zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvmbfl4zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-curve" /></template>
