<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5nw-84yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5nw-84yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opencv" /></template>
