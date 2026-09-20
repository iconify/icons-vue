<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ag6wukp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ag6wukp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zedindustries" /></template>
