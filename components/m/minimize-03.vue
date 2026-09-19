<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-fk03d_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-fk03d_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:minimize-03" /></template>
