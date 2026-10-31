<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3lw875_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3lw875_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:martini-gloss" /></template>
