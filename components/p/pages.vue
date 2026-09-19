<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puz4ss72c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puz4ss72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:pages" /></template>
