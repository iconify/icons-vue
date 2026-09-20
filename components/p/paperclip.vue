<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjy585wqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjy585wqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:paperclip" /></template>
