<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-cvvactf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z-cvvactf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sofa-remix" /></template>
