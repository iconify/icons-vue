<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmx8dccer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wmx8dccer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:street-sign-remix" /></template>
