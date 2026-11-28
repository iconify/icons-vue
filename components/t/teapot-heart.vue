<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csb1qxakk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csb1qxakk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:teapot-heart" /></template>
