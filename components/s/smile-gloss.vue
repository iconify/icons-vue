<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p04vnh08p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p04vnh08p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smile-gloss" /></template>
