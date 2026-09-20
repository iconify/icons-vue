<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg8495bbv.css';
import '../../css/z/zdj1fdckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg8495bbv"/><path clip-rule="evenodd" class="zdj1fdckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unstructured" /></template>
