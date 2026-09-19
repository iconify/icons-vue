<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za-3b2xgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="za-3b2xgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nginx" /></template>
