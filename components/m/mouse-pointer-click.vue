<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr5l8bckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr5l8bckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-click" /></template>
