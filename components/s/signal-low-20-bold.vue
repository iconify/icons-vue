<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsw7geboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bsw7geboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-low-20-bold" /></template>
