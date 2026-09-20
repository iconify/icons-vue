<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_ddctbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_ddctbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-collaborate-group-remix" /></template>
