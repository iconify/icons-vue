<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj9b4dbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj9b4dbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:wine-glass-empty-solid" /></template>
