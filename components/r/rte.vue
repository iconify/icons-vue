<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha9j5psdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha9j5psdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rte" /></template>
