<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j01r4uprb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j01r4uprb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-outline" /></template>
