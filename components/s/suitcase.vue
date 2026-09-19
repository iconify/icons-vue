<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puz4nbclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puz4nbclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:suitcase" /></template>
