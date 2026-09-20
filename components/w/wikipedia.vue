<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz0800s7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz0800s7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wikipedia" /></template>
