<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkv-4ibcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkv-4ibcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vector-square" /></template>
