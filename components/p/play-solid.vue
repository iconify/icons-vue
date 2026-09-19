<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh_ti6dfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_ti6dfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:play-solid" /></template>
