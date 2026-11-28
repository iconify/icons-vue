<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uokly3bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uokly3bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:thumbs-down" /></template>
