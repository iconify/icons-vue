<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1b1l1b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p1b1l1b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wheel" /></template>
