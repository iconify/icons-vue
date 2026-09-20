<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-5h5pbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-5h5pbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-up" /></template>
