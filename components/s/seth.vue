<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdfcs7bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdfcs7bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:seth" /></template>
