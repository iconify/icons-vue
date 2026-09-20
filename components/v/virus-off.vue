<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz73jkslc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz73jkslc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:virus-off" /></template>
