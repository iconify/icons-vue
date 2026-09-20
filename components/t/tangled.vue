<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p27bqc3bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p27bqc3bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tangled" /></template>
