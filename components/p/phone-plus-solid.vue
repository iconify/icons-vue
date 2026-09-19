<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhbjm3lzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhbjm3lzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-plus-solid" /></template>
