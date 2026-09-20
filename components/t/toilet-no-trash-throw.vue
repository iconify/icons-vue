<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syr7h0fyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syr7h0fyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:toilet-no-trash-throw" /></template>
