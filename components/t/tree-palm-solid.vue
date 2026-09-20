<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hax9i4bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hax9i4bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tree-palm-solid" /></template>
