<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4se2mm0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f4se2mm0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:programclose" /></template>
