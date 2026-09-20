<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxfrac8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":220,"height":220};
const content = `<path clip-rule="evenodd" class="qlxfrac8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pinecone" /></template>
