<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or9negxph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="or9negxph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rectangleselection" /></template>
