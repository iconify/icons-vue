<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvugenbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gvugenbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-grid-2x2-fill" /></template>
