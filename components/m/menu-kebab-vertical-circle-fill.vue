<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxxn7yb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxxn7yb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical-circle-fill" /></template>
