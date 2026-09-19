<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d75lzfbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d75lzfbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-5" /></template>
