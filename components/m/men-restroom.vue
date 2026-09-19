<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmuim6abs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmuim6abs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:men-restroom" /></template>
