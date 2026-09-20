<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yka21ub2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yka21ub2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:swap-3-fill" /></template>
