<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvl8subgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pvl8subgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:objective-c" /></template>
