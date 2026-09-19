<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bign-sb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bign-sb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:picture-square" /></template>
