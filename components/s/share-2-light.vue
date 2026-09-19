<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdeum2vmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdeum2vmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-2-light" /></template>
