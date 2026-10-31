<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxk67cb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxk67cb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-alt-round" /></template>
