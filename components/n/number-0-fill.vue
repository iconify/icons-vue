<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnmqqabxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnmqqabxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-0-fill" /></template>
