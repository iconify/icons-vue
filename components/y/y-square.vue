<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi24mtzvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zi24mtzvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:y-square" /></template>
