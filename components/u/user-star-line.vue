<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxw6qj_ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxw6qj_ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-star-line" /></template>
