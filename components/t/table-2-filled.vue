<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_nj2bbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_nj2bbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:table-2-filled" /></template>
