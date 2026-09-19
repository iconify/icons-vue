<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp_4ch6qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="xp_4ch6qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:text-height" /></template>
