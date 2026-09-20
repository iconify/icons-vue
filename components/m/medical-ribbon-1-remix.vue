<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvxd9ribf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nvxd9ribf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-ribbon-1-remix" /></template>
