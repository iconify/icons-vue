<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn7fs3i6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pn7fs3i6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paragraph-article-solid" /></template>
