<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isjsz3ejb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isjsz3ejb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:thumbsup" /></template>
