<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5thofbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l5thofbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:speaker-1-remix" /></template>
