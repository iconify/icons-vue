<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddkj1ibij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddkj1ibij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield-fill" /></template>
