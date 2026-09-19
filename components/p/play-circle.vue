<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr70xqm1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nr70xqm1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:play-circle" /></template>
