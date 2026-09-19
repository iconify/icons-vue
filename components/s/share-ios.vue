<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn3fw0byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn3fw0byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:share-ios" /></template>
