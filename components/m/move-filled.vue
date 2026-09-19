<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjkj1o2_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjkj1o2_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:move-filled" /></template>
