<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbk7628lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gbk7628lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:mouse-fill" /></template>
