<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poy4shutt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poy4shutt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ruff" /></template>
