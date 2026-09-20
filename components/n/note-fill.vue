<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5v5fg1lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5v5fg1lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:note-fill" /></template>
