<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlw6o2bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlw6o2bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:scan" /></template>
