<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acy2isbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="acy2isbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:play" /></template>
