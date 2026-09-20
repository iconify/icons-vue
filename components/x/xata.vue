<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2r4mmblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":134,"height":135};
const content = `<path clip-rule="evenodd" class="k2r4mmblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xata" /></template>
