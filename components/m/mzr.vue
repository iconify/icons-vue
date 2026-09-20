<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zovxy3blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zovxy3blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mzr" /></template>
