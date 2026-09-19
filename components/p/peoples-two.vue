<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwsj9qblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bwsj9qblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:peoples-two" /></template>
