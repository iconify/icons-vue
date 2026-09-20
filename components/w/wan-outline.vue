<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odqf5ztvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="odqf5ztvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wan-outline" /></template>
