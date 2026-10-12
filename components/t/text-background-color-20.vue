<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqm9qnbgq.css';
import '../../css/u/u5ujo24lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqm9qnbgq"/><path class="u5ujo24lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-background-color-20" /></template>
