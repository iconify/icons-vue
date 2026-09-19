<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9pvjwbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1026};
const content = `<path class="r9pvjwbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:textlayer" /></template>
