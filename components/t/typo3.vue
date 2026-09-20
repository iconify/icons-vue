<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5491bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="di5491bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:typo3" /></template>
