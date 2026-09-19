<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmap0gbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1408};
const content = `<path class="fmap0gbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tablet" /></template>
