<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4pj5ib5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4pj5ib5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-click" /></template>
