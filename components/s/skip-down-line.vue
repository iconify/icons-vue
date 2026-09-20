<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvf67sgcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvf67sgcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-down-line" /></template>
