<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4jwv82w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4jwv82w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pinecone-solid" /></template>
