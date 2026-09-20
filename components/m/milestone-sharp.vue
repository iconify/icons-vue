<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc4nnrbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc4nnrbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:milestone-sharp" /></template>
