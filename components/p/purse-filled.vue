<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdwk85bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdwk85bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:purse-filled" /></template>
