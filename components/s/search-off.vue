<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja_m97byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja_m97byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:search-off" /></template>
