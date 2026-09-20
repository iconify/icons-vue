<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5fc605jj.css';
import '../../css/v/vrumybbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5fc605jj"/><path clip-rule="evenodd" class="vrumybbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-portrait-16" /></template>
