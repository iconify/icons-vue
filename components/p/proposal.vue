<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of117qg0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="of117qg0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:proposal" /></template>
