<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-u_94fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="x1-u_94fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:superscript-solid" /></template>
