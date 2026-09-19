<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u69-hex5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u69-hex5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:message-text-solid" /></template>
