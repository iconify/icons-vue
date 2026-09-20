<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbf1ts0hu.css';
import '../../css/f/fcgr3_agr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rbf1ts0hu"/><path clip-rule="evenodd" class="fcgr3_agr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:money-16" /></template>
