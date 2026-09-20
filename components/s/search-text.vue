<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnk0yztxu.css';
import '../../css/x/x8-usg97v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="bnk0yztxu"/><path clip-rule="evenodd" class="x8-usg97v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search-text" /></template>
