<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifu7oub2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifu7oub2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:text-formating-subscript" /></template>
