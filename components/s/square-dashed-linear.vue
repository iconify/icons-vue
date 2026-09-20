<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xka43fg1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xka43fg1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-dashed-linear" /></template>
