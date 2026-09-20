<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkale4bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wkale4bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:text-square-remix" /></template>
