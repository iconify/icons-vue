<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3g7597sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="c3g7597sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mouse" /></template>
