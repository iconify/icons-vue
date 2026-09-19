<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d25c1tbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d25c1tbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-subtract-filled" /></template>
