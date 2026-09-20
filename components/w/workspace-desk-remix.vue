<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruyml-dmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruyml-dmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:workspace-desk-remix" /></template>
