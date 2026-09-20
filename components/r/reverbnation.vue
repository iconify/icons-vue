<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs69evbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs69evbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:reverbnation" /></template>
