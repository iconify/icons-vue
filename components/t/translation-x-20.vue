<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaz4rm-bq.css';
import '../../css/k/kpyqg9v7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uaz4rm-bq"/><path class="kpyqg9v7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-x-20" /></template>
