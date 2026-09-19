<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npyt5pblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npyt5pblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-bag-outline" /></template>
