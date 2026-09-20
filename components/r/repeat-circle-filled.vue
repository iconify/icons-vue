<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctes0nbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctes0nbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:repeat-circle-filled" /></template>
