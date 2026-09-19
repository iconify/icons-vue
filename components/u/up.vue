<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7lxg49ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7lxg49ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:up" /></template>
