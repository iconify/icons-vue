<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7gypjs_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7gypjs_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:paint-brush-alt-filled" /></template>
