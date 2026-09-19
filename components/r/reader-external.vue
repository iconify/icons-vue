<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0deju9uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0deju9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-external" /></template>
