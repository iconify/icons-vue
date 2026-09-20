<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y67uuy_3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y67uuy_3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:marvelapp" /></template>
