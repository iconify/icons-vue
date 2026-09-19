<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9lz5abtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9lz5abtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:vertical-merge" /></template>
