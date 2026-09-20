<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n27emnbuv.css';
import '../../css/x/x_3uzco3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n27emnbuv"/><rect class="x_3uzco3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:markdoc" /></template>
