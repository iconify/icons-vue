<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc78d-b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc78d-b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video-off" /></template>
