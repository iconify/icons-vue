<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qza-7dbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qza-7dbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:unsplash" /></template>
