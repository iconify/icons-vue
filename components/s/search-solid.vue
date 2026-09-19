<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhr6axbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhr6axbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:search-solid" /></template>
