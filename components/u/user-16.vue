<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1u65mb1a.css';
import '../../css/e/e6siqkbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z1u65mb1a"/><path clip-rule="evenodd" class="e6siqkbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:user-16" /></template>
