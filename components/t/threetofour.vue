<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pufi5ikpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="pufi5ikpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:threetofour" /></template>
