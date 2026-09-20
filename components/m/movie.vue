<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67dilbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g67dilbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:movie" /></template>
