<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1w1m-zwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b1w1m-zwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:merge-vertical-flat" /></template>
