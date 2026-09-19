<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi4i2zbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yi4i2zbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-1-fill" /></template>
