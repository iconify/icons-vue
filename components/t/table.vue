<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2tj91baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2tj91baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:table" /></template>
