<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmrufobix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bmrufobix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:serving-dome-hand" /></template>
