<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxfuyzbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxfuyzbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play" /></template>
