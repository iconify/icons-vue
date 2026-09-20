<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgwml-q3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgwml-q3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:upload-computer-remix" /></template>
