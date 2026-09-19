<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7s__0boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7s__0boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:share-two" /></template>
