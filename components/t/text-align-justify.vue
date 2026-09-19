<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av5bkeb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av5bkeb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-justify" /></template>
