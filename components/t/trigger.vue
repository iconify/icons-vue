<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1fd39d2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="e1fd39d2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:trigger" /></template>
