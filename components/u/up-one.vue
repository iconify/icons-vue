<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3wdbkblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n3wdbkblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:up-one" /></template>
