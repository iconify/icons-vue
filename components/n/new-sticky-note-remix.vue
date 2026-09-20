<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7tonmbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7tonmbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:new-sticky-note-remix" /></template>
