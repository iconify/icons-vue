<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32p1abwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h32p1abwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:unsplash" /></template>
