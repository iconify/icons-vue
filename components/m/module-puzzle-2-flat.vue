<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqoogac1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqoogac1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:module-puzzle-2-flat" /></template>
