<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbl1uabtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbl1uabtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:resize-field" /></template>
