<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yojs9sdcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yojs9sdcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scroll-filled" /></template>
