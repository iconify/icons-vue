<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc86mwvot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gc86mwvot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-h" /></template>
