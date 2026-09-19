<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1pa7kbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1pa7kbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-horizontal-circle-fill" /></template>
