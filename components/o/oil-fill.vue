<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l87bt4btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l87bt4btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:oil-fill" /></template>
