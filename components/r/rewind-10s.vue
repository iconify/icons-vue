<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncx9_cchy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncx9_cchy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind-10s" /></template>
