<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcvha2kxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcvha2kxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:sort-ascending" /></template>
