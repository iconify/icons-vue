<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf5ttjbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf5ttjbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tennis-ball-fill-round" /></template>
