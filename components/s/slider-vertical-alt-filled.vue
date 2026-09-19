<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gltjvwbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gltjvwbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slider-vertical-alt-filled" /></template>
