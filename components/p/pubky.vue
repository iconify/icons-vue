<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lymkkoqmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lymkkoqmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pubky" /></template>
