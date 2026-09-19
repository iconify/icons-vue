<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3u07guut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="h3u07guut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:viber" /></template>
