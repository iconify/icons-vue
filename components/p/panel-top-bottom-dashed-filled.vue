<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgsf-tbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgsf-tbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-top-bottom-dashed-filled" /></template>
