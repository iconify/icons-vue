<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhdo3bc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdo3bc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tumblr-filled" /></template>
