<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4hnid7qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4hnid7qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:television-table" /></template>
