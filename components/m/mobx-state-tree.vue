<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhgrmca3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhgrmca3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mobx-state-tree" /></template>
