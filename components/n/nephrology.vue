<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc7o-gtnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zc7o-gtnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nephrology" /></template>
