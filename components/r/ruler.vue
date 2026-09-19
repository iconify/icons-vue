<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9xr5p5ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9xr5p5ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:ruler" /></template>
