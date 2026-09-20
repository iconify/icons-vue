<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpjt_glcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpjt_glcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:peace-symbol" /></template>
