<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr69i1bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr69i1bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-down2" /></template>
