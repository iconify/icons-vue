<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdzpb5b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdzpb5b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:meme" /></template>
