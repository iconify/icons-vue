<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzt74d93r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzt74d93r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggle-big-right-filled" /></template>
