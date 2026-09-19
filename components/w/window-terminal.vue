<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqq8e0bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqq8e0bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:window-terminal" /></template>
