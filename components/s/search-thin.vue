<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zug9xsbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zug9xsbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:search-thin" /></template>
