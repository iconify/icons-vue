<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep6qygbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6qygbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-book-bold" /></template>
