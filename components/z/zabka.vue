<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emx2i_-og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emx2i_-og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zabka" /></template>
