<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to4xgtbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to4xgtbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tldraw-light" /></template>
