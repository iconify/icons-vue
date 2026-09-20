<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvnqboqvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvnqboqvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-square-filled" /></template>
