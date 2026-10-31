<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh8rubmwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh8rubmwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-plus-corner-round" /></template>
