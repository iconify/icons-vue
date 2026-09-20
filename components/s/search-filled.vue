<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctn77yx1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctn77yx1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:search-filled" /></template>
