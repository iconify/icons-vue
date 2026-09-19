<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiwkhfbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="wiwkhfbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:textfield" /></template>
