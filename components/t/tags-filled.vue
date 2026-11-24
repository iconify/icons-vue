<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3is4ubde.css';
import '../../css/z/z283bdcgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3is4ubde"/><path clip-rule="evenodd" class="z283bdcgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tags-filled" /></template>
